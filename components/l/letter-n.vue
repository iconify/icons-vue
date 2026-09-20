<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk7y_4b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hk7y_4b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-n" /></template>
