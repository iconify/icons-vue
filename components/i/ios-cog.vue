<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r79mn2bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r79mn2bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cog" /></template>
