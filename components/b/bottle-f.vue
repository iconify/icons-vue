<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4j_5erem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="c4j_5erem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bottle-f" /></template>
