<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz2fa8bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz2fa8bim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:box" /></template>
