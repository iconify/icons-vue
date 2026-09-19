<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhbk6obna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yhbk6obna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:magnet" /></template>
