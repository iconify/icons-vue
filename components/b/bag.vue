<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au-v0i33b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au-v0i33b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:bag" /></template>
