<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl-s0jbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl-s0jbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:candy-gloss" /></template>
