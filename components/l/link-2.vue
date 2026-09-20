<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k12150_0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k12150_0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:link-2" /></template>
