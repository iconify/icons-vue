<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghjewjjog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghjewjjog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-square-solid" /></template>
