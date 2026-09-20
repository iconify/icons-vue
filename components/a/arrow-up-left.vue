<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj4j7xbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj4j7xbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-up-left" /></template>
