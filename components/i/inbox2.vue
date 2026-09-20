<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqae8lbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zqae8lbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:inbox2" /></template>
