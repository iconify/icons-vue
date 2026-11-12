<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc5njjxlp.css';
import '../../css/b/bjzxtacce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rc5njjxlp"/><path class="bjzxtacce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filegator-dark" /></template>
