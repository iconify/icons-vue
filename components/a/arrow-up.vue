<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqt48ib6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqt48ib6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:arrow-up" /></template>
