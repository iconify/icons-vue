<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbx-v0bcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbx-v0bcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dicebear" /></template>
