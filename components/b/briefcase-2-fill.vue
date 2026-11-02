<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v89uo1arz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v89uo1arz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:briefcase-2-fill" /></template>
