<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9hzgob4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i9hzgob4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:angle-right-solid" /></template>
