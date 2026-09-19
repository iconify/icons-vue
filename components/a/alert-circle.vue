<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj_biz8vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fj_biz8vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alert-circle" /></template>
