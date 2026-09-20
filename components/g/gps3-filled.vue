<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vze3wnqfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vze3wnqfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gps3-filled" /></template>
