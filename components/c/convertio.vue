<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5w8rdb-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5w8rdb-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:convertio" /></template>
