<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byvzk5lvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byvzk5lvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-close-fill" /></template>
