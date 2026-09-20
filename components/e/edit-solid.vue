<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1-0k9v-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1-0k9v-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:edit-solid" /></template>
