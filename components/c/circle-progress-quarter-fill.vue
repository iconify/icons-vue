<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbr34pbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbr34pbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-progress-quarter-fill" /></template>
