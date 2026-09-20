<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irboz257l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irboz257l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:imagedotsc" /></template>
