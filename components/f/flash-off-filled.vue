<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g39pp1bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g39pp1bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:flash-off-filled" /></template>
