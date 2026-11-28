<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcca3lbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vcca3lbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:golf-duotone" /></template>
