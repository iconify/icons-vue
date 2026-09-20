<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh2zh0bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh2zh0bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-down2" /></template>
