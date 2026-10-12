<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7mn0ssnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b7mn0ssnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:earth-stroke-20" /></template>
