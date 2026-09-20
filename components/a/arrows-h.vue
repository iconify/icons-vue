<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6tczdnnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="a6tczdnnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrows-h" /></template>
