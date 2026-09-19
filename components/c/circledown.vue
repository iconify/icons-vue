<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6u4jdb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m6u4jdb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circledown" /></template>
