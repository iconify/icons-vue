<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5lj9sbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5lj9sbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:location-outlined" /></template>
