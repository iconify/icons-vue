<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6tplefgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="r6tplefgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:3" /></template>
