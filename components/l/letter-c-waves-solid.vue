<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah9kv2bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah9kv2bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-c-waves-solid" /></template>
