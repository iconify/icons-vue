<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajhar0bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajhar0bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:delete" /></template>
