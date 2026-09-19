<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iue2-2gxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iue2-2gxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:chip" /></template>
