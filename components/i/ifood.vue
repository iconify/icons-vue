<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5s_7db0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5s_7db0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ifood" /></template>
