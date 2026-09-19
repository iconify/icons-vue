<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c208yhbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c208yhbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:jar-wheat-outline" /></template>
