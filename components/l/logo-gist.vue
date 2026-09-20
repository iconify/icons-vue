<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxeawbdpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":16};
const content = `<path class="wxeawbdpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:logo-gist" /></template>
