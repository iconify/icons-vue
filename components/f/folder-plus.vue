<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_ntu7akw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_ntu7akw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:folder-plus" /></template>
