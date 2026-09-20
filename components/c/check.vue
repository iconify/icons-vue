<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrjb4xbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrjb4xbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:check" /></template>
