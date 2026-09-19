<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz1nshtzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pz1nshtzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:dagger" /></template>
