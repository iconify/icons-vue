<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht23lqber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht23lqber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:android" /></template>
