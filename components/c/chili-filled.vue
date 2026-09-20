<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv23_d22h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv23_d22h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chili-filled" /></template>
