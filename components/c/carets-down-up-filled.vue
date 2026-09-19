<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhmfapelv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhmfapelv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:carets-down-up-filled" /></template>
