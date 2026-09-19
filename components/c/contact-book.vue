<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv8augtve.css';
import '../../css/c/cqedrde9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv8augtve"/><path class="cqedrde9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:contact-book" /></template>
