<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mss06q77o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mss06q77o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-line" /></template>
