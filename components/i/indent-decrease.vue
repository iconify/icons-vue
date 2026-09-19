<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_ilgq-0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b_ilgq-0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:indent-decrease" /></template>
