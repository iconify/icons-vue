<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb1bdbcsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wb1bdbcsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:google-drive" /></template>
