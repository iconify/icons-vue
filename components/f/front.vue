<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3cyo1ucc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a3cyo1ucc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:front" /></template>
