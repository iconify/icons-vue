<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkwc33ays.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gkwc33ays"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-down-right2" /></template>
