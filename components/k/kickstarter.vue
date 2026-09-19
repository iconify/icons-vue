<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2kv7-_oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2kv7-_oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:kickstarter" /></template>
