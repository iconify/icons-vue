<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py3j6kbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py3j6kbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:label-off-outline" /></template>
