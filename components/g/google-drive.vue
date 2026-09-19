<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8dmnm1kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z8dmnm1kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:google-drive" /></template>
