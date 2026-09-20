<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-05gybft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-05gybft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-double-left" /></template>
