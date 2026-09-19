<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vankhpb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vankhpb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ai" /></template>
