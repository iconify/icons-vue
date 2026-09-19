<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2sbr4uqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="q2sbr4uqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hydrant" /></template>
