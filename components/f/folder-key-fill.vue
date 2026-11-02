<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi_hpibjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi_hpibjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-key-fill" /></template>
