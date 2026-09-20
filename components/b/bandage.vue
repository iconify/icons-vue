<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sas56hbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sas56hbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bandage" /></template>
