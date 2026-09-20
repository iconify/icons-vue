<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3i_3jbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3i_3jbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:inbox-2-fill" /></template>
