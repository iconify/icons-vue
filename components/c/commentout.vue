<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkauw5mui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="bkauw5mui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:commentout" /></template>
