<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4ra9hb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4ra9hb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heart-minus-solid" /></template>
