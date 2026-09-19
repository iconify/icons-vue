<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1t6bcc2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1t6bcc2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:bug" /></template>
