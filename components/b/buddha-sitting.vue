<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zc9mq5byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zc9mq5byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:buddha-sitting" /></template>
