<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spjx-7o2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="spjx-7o2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:band-aid" /></template>
