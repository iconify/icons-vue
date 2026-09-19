<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b09-5jb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b09-5jb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:double-quote-sans-right" /></template>
