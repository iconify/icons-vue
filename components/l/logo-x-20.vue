<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik425sgmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ik425sgmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:logo-x-20" /></template>
