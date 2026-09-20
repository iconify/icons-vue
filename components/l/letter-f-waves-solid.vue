<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ze2r_i9qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ze2r_i9qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-f-waves-solid" /></template>
