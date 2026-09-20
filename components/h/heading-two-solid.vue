<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acyf46khq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acyf46khq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:heading-two-solid" /></template>
