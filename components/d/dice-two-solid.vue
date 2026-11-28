<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtrqm0byr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtrqm0byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dice-two-solid" /></template>
