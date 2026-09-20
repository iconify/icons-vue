<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-oilbfst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-oilbfst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:leaf" /></template>
