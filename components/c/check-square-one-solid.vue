<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eic95nb5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eic95nb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:check-square-one-solid" /></template>
