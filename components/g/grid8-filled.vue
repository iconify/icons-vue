<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r24k1jfmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r24k1jfmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid8-filled" /></template>
