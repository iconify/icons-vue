<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akho15b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="akho15b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chalkboard-user" /></template>
