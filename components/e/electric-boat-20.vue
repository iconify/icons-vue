<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1weu1kyu.css';
import '../../css/d/dzk9j3baz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h1weu1kyu"/><path class="dzk9j3baz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-boat-20" /></template>
