<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0vmcjw3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0vmcjw3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-double-up" /></template>
