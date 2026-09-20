<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0o5wjnji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="h0o5wjnji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:align-left" /></template>
