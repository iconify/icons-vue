<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx9bgwqht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xx9bgwqht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:drive" /></template>
