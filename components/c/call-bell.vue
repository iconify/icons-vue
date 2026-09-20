<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoxm453wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uoxm453wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:call-bell" /></template>
