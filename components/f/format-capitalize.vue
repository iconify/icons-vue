<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg9ccc5ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="lg9ccc5ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:format-capitalize" /></template>
