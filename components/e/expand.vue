<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf9136b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="zf9136b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:expand" /></template>
