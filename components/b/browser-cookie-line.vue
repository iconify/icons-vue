<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lajp-mbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lajp-mbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:browser-cookie-line" /></template>
