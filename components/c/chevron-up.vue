<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_awtobjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-7.5};
const content = `<path class="a_awtobjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-up" /></template>
