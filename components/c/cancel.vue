<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h190_updm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h190_updm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cancel" /></template>
