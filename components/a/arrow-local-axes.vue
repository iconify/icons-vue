<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3_jp68jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k3_jp68jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-local-axes" /></template>
