<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfexlwteu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jfexlwteu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:chat-alt" /></template>
