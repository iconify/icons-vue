<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxk4400ub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xxk4400ub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:link" /></template>
