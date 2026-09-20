<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo7cxv9ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo7cxv9ak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:helium" /></template>
