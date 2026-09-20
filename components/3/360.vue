<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urq8ylumb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="urq8ylumb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:360" /></template>
