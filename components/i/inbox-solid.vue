<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlb4bxb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlb4bxb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:inbox-solid" /></template>
