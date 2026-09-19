<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-_12jovm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="i-_12jovm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cssthree" /></template>
