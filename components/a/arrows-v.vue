<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6azs0btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="g6azs0btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrows-v" /></template>
