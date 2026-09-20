<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w42rvhb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w42rvhb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:grid" /></template>
