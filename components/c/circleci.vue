<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijr65rbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijr65rbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:circleci" /></template>
