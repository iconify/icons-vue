<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9k_4b-vj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9k_4b-vj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:divide-solid" /></template>
