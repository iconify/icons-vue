<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awtstmbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":999};
const content = `<path class="awtstmbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:domain" /></template>
