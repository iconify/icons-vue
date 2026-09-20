<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsy3wcbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsy3wcbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bad-laugh-filled" /></template>
