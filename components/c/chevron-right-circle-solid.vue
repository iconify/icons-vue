<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djoi96bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djoi96bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:chevron-right-circle-solid" /></template>
