<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m14mvl26y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m14mvl26y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:arrow-up-down-3" /></template>
