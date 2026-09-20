<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3rw4bb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3rw4bb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:checkbox-circle-fill" /></template>
