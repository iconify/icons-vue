<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nil35lbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":543,"height":768};
const content = `<path class="nil35lbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:ink" /></template>
