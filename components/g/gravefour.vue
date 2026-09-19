<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbo-9nggs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bbo-9nggs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:gravefour" /></template>
