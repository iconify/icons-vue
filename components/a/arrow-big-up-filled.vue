<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oez6-234v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oez6-234v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-big-up-filled" /></template>
