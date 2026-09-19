<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrgrc1b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrgrc1b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:adobe-creative-cloud" /></template>
