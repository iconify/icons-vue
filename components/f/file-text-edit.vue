<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j704ljfdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j704ljfdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-text-edit" /></template>
