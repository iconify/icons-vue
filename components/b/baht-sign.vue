<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0o33vb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="n0o33vb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:baht-sign" /></template>
