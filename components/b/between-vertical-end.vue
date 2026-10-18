<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5bxur4ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5bxur4ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:between-vertical-end" /></template>
