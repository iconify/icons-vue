<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqud1uhki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqud1uhki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-left-circle-solid" /></template>
