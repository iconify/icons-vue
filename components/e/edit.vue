<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5u_hrb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5u_hrb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:edit" /></template>
