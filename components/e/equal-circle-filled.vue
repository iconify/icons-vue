<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmzh3rb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmzh3rb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:equal-circle-filled" /></template>
