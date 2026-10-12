<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giez_00ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giez_00ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-filled" /></template>
