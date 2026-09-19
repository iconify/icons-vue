<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umx-hub4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umx-hub4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:briefcase-alt" /></template>
