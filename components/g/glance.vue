<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuysp5byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuysp5byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:glance" /></template>
