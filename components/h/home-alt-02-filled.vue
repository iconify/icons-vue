<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_qnqib-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_qnqib-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:home-alt-02-filled" /></template>
