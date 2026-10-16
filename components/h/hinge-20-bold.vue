<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5u49bxgz.css';
import '../../css/n/n-rap1bom.css';
import '../../css/e/ehybfubeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n5u49bxgz"/><path class="n-rap1bom"/><path class="ehybfubeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hinge-20-bold" /></template>
