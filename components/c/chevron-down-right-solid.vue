<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwi16yuep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwi16yuep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-down-right-solid" /></template>
