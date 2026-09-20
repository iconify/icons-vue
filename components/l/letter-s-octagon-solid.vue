<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6owe0blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6owe0blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-s-octagon-solid" /></template>
