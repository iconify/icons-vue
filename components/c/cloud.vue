<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnfh_j-gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":819,"height":620};
const content = `<path class="dnfh_j-gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:cloud" /></template>
