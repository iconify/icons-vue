<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glm38kbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="glm38kbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:church" /></template>
