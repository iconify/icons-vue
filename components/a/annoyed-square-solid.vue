<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo4k8bv1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo4k8bv1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:annoyed-square-solid" /></template>
