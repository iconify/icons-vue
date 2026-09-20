<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cowvln-sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cowvln-sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:clock-one-solid" /></template>
