<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or_486byj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or_486byj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-top-tail" /></template>
