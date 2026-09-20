<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdbxjtq0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdbxjtq0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:image-add" /></template>
