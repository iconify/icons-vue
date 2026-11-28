<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg8nfu2xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg8nfu2xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:git-merge" /></template>
