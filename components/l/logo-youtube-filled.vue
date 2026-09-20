<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lot__bbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lot__bbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-youtube-filled" /></template>
