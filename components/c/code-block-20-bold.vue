<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-w1mof7v.css';
import '../../css/d/dod-re5li.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b-w1mof7v"/><path class="dod-re5li"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:code-block-20-bold" /></template>
