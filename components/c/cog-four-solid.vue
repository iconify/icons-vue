<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge-76lk_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ge-76lk_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cog-four-solid" /></template>
