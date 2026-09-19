<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7kh2ac5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="s7kh2ac5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:folder-fill-badge-person-crop" /></template>
