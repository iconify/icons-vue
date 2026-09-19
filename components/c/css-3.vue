<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z370rgiey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z370rgiey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:css-3" /></template>
