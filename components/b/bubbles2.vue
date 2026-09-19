<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q29bvxb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":16};
const content = `<path class="q29bvxb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:bubbles2" /></template>
