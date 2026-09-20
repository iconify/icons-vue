<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp_dbydas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp_dbydas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:award-fill" /></template>
