<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_7y3xbjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_7y3xbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:currency-pound" /></template>
