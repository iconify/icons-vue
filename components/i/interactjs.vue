<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfnd-01kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfnd-01kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:interactjs" /></template>
