<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s54r1xbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s54r1xbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:form" /></template>
