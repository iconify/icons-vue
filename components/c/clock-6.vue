<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnasulsdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnasulsdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:clock-6" /></template>
