<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2s5geiwy.css';
import '../../css/s/s3-5j4bzw.css';
import '../../css/c/clg0t333v.css';
import '../../css/y/yls8p4b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i2s5geiwy"/><path class="s3-5j4bzw"/><path class="clg0t333v"/><path class="yls8p4b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chalet-20-bold" /></template>
