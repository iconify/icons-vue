<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhz01_o5b.css';
import '../../css/d/d2kvgvbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVG8KAPOcZt" class="nhz01_o5b"/></defs><use href="#SVG8KAPOcZt" transform="translate(2 4)" class="d2kvgvbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:imac-outlined" /></template>
