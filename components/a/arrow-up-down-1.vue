<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ridpunbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ridpunbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-up-down-1" /></template>
