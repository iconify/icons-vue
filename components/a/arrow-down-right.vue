<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re34m18fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="re34m18fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-down-right" /></template>
