<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afjig_b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="afjig_b2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:couch" /></template>
