<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bms8p0b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bms8p0b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dam-1-filled" /></template>
