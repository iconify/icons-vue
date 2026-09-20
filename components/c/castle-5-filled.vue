<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-9vmjg_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-9vmjg_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:castle-5-filled" /></template>
