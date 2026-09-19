<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1-wjbbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g1-wjbbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:extjs" /></template>
