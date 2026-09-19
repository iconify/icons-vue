<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl4opnbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zl4opnbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:goat-filled" /></template>
