<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp8lvw4jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="jp8lvw4jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:googledrive" /></template>
