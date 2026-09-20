<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx0z5_a3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx0z5_a3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid7" /></template>
