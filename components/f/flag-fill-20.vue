<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3d0l7jvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n3d0l7jvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:flag-fill-20" /></template>
