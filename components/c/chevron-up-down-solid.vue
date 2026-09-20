<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khg_sbbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khg_sbbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-down-solid" /></template>
