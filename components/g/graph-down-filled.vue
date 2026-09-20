<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y90172upd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y90172upd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:graph-down-filled" /></template>
