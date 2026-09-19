<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6oimmbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6oimmbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:filter" /></template>
