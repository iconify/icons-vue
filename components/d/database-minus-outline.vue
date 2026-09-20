<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqavzjbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqavzjbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:database-minus-outline" /></template>
