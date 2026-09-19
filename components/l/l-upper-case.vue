<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0su68bht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="c0su68bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:l-upper-case" /></template>
