<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeap7yb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeap7yb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-left-solid" /></template>
