<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of8voccif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of8voccif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:font" /></template>
