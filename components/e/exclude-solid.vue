<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgyb_l4ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgyb_l4ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:exclude-solid" /></template>
