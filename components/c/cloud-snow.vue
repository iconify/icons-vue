<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r38p8sv5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r38p8sv5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:cloud-snow" /></template>
