<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz7du6xnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz7du6xnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:checkmark-outline" /></template>
