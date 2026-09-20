<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv06cbbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fv06cbbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:contactless-solid" /></template>
