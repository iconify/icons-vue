<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv22kw38n.css';
import '../../css/m/mo7-9cc3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="kv22kw38n"/><path class="mo7-9cc3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:add-1y" /></template>
