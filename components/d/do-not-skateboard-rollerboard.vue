<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq13s4qpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq13s4qpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:do-not-skateboard-rollerboard" /></template>
