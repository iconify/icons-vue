<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc9m0jmpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc9m0jmpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-left-square-solid" /></template>
