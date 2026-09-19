<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxxksqb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pxxksqb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:cloudy" /></template>
