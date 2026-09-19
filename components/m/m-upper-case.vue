<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_2gwyvwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="y_2gwyvwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:m-upper-case" /></template>
