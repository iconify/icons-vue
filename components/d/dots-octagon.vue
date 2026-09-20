<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t07md_6bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t07md_6bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-octagon" /></template>
