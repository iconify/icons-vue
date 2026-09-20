<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb3enpbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb3enpbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:insurance-head-bold" /></template>
