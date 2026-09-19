<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au06jsb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="au06jsb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-curve" /></template>
