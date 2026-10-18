<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdgqpge4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdgqpge4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-justify-center" /></template>
