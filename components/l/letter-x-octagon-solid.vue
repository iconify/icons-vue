<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k88o-jb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k88o-jb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-x-octagon-solid" /></template>
