<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmj4v3web.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="jmj4v3web"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:comment-alt" /></template>
