<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tll6oktfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="tll6oktfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bitbucket" /></template>
