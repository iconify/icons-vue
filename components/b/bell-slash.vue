<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b19ec7c9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="b19ec7c9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:bell-slash" /></template>
