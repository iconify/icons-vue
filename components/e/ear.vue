<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7nz21b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7nz21b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ear" /></template>
