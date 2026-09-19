<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_z1gpoxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s_z1gpoxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-up-right-circle-fill" /></template>
