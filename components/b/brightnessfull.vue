<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbzh3mn8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jbzh3mn8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:brightnessfull" /></template>
