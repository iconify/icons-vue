<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj264xb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj264xb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heading-5-solid" /></template>
