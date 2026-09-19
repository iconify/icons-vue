<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrej8qxjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zrej8qxjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-text-justify-all" /></template>
