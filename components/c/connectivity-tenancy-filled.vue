<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azy9twppz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azy9twppz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:connectivity-tenancy-filled" /></template>
