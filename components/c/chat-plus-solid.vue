<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvf_jtchl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvf_jtchl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chat-plus-solid" /></template>
