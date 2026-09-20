<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaybjhg_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uaybjhg_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:calendar-add-solid" /></template>
