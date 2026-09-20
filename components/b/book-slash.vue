<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzf_cpbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzf_cpbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:book-slash" /></template>
