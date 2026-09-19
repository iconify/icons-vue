<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqw1kdbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqw1kdbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:carbon-offset" /></template>
