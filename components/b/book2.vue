<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0y3sbbpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0y3sbbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:book2" /></template>
