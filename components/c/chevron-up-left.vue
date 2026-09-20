<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bimjldq8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bimjldq8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-left" /></template>
