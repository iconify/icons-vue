<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr4gv3myf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nr4gv3myf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:chat-alt-2" /></template>
