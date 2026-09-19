<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmqvwcc6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bmqvwcc6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:join-right-outer" /></template>
