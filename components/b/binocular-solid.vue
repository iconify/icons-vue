<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gi2996b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gi2996b1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:binocular-solid" /></template>
