<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zurmcyjfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zurmcyjfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:grid-small-round" /></template>
