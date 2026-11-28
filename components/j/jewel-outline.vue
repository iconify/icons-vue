<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjyrm0bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kjyrm0bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:jewel-outline" /></template>
