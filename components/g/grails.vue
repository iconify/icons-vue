<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws22k8poc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ws22k8poc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:grails" /></template>
