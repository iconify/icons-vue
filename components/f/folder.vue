<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz12_jbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="cz12_jbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:folder" /></template>
