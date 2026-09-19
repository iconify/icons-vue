<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chkf3ns7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="chkf3ns7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:circle-stop" /></template>
