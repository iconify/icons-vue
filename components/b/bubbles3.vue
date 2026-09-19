<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz-_py4dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":18,"height":16};
const content = `<path class="pz-_py4dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:bubbles3" /></template>
