<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xax6l7bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xax6l7bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:adobe-lightroom-solid" /></template>
