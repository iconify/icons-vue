<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na3cc9g2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na3cc9g2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:google-solid" /></template>
