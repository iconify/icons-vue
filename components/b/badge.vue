<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbskt6s3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbskt6s3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:badge" /></template>
