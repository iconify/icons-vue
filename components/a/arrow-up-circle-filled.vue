<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcdl0kf_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcdl0kf_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-up-circle-filled" /></template>
