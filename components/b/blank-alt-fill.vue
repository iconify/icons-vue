<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykp4-zbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ykp4-zbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:blank-alt-fill" /></template>
