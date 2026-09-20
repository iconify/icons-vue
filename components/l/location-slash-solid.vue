<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4x23oj2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4x23oj2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:location-slash-solid" /></template>
