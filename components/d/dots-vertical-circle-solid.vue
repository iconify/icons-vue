<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq-64-z-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq-64-z-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dots-vertical-circle-solid" /></template>
