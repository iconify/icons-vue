<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q04vhtbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q04vhtbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-up-right-square-solid" /></template>
