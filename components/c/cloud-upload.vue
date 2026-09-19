<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjzrinolv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjzrinolv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:cloud-upload" /></template>
