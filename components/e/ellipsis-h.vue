<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btwot6bhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btwot6bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:ellipsis-h" /></template>
