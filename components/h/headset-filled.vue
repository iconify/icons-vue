<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5qiftb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5qiftb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:headset-filled" /></template>
