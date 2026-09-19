<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xajp4ebgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xajp4ebgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:adobe-photoshop-solid" /></template>
