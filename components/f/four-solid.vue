<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvdo4znfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvdo4znfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:four-solid" /></template>
