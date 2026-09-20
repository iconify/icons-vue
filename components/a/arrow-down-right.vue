<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9pmgkkgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="b9pmgkkgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:arrow-down-right" /></template>
