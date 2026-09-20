<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3hw1xbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3hw1xbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:black-hole3-filled" /></template>
