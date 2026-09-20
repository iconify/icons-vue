<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi7u_f7uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi7u_f7uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-vertical-waves" /></template>
