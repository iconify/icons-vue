<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scaub_b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scaub_b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:locate-filled" /></template>
