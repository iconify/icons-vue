<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm57pugyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qm57pugyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:apart" /></template>
