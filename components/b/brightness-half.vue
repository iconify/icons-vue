<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqoppnb6n.css';
import '../../css/c/cv9731b4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqoppnb6n"/><path class="cv9731b4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:brightness-half" /></template>
