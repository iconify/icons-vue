<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb45ydbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mb45ydbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-plus-filled" /></template>
