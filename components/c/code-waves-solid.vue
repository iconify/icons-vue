<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb91mbb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb91mbb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:code-waves-solid" /></template>
