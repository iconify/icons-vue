<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9-del4gd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w9-del4gd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kolors" /></template>
