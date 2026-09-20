<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9n_yslph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="v9n_yslph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-outer-light-dashed-down-left-right" /></template>
