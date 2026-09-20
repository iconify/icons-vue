<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygys6hbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygys6hbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kickstarter" /></template>
