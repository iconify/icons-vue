<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zry5a9qkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zry5a9qkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:folder-minus-solid" /></template>
