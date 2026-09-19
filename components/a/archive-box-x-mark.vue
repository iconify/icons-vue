<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-_ib7i3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_ib7i3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:archive-box-x-mark" /></template>
