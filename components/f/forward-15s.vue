<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ces36_uah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ces36_uah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forward-15s" /></template>
