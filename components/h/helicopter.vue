<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8b-1acnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":704};
const content = `<path class="t8b-1acnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:helicopter" /></template>
