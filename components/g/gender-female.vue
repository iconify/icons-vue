<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/potr8dbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="potr8dbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gender-female" /></template>
