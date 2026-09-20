<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5l26jbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5l26jbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:crystal" /></template>
