<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5nysbo_z.css';
import '../../css/n/nfn_d0zln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r5nysbo_z"/><path class="nfn_d0zln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cix" /></template>
