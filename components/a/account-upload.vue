<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu6dahboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu6dahboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-upload" /></template>
