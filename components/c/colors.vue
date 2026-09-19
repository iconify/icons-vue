<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnrni5tmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnrni5tmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:colors" /></template>
