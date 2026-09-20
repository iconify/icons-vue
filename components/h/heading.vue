<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jia3v4fcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jia3v4fcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:heading" /></template>
