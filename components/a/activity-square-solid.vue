<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8an-8bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8an-8bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:activity-square-solid" /></template>
