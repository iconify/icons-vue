<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck8nk4b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck8nk4b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:inbox-archive-solid" /></template>
