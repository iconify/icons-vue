<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed9bqxbqe.css';
import '../../css/z/z_agvsb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ed9bqxbqe"/><path class="z_agvsb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:header-4-20" /></template>
