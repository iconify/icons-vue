<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp23xbcqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sp23xbcqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:chakraui-wordmark" /></template>
