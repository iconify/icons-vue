<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrqlv4q8g.css';
import '../../css/g/gc181eckg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrqlv4q8g"/><path class="gc181eckg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendars-filled" /></template>
