<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yevwt22qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yevwt22qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-smile-sharp-fill" /></template>
