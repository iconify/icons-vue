<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzho85dns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jzho85dns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-edit-alt-2-line" /></template>
