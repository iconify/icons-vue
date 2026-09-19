<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2o6bplzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2o6bplzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:down-arrow-circle" /></template>
