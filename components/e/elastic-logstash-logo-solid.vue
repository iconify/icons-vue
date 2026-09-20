<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5-7tvbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y5-7tvbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:elastic-logstash-logo-solid" /></template>
