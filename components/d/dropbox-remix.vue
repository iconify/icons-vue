<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzyis_bds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mzyis_bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:dropbox-remix" /></template>
