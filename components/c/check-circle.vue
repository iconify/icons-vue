<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev9-qvtll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev9-qvtll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:check-circle" /></template>
