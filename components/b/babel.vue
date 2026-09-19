<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kev98l2gj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kev98l2gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:babel" /></template>
