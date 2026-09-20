<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usgsh8fjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usgsh8fjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrows-rotate" /></template>
