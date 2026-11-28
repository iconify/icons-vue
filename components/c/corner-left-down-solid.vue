<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9q7kbbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9q7kbbig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:corner-left-down-solid" /></template>
