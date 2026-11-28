<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahch_tvuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ahch_tvuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:baby" /></template>
