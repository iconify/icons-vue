<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo8ai3bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo8ai3bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-right-waves-solid" /></template>
