<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yef7qlvgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yef7qlvgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:couchbase" /></template>
