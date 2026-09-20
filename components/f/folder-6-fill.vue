<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o38tsc_lv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o38tsc_lv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-6-fill" /></template>
