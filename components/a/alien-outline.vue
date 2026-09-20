<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riiwu8b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="riiwu8b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:alien-outline" /></template>
