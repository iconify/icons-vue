<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh5xogo6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mh5xogo6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-down-square-filled" /></template>
