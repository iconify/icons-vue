<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w43g67bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w43g67bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:coppel" /></template>
