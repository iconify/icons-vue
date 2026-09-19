<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e50c8gb5g.css';
import '../../css/u/ut5kjkb9c.css';
import '../../css/m/mry1nj2og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e50c8gb5g"/><path class="ut5kjkb9c"/><path class="mry1nj2og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:binary-authorization" /></template>
