<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvf-h2b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wvf-h2b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:boy-filled" /></template>
