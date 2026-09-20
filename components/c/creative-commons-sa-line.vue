<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj13829qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj13829qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:creative-commons-sa-line" /></template>
