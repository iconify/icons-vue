<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scmajvbqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scmajvbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:flip-v-alt" /></template>
