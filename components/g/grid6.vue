<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu247bctc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bu247bctc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid6" /></template>
