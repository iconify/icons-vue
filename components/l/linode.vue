<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdudxp5df.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="tdudxp5df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:linode" /></template>
