<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4mbnrhsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4mbnrhsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:beaker-24" /></template>
