<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ansqsn_cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ansqsn_cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:chevron-right" /></template>
