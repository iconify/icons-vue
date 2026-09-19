<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c542o2ulc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c542o2ulc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:button" /></template>
