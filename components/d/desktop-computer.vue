<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybbik6bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybbik6bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:desktop-computer" /></template>
