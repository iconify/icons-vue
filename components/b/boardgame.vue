<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqtmd9bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="xqtmd9bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:boardgame" /></template>
