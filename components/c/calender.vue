<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k38g4obld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k38g4obld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:calender" /></template>
