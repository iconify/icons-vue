<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2g9_5bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p2g9_5bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:info" /></template>
