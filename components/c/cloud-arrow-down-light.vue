<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm8d_x7vj.css';
import '../../css/r/rdm-ltbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jm8d_x7vj"/><path class="rdm-ltbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cloud-arrow-down-light" /></template>
