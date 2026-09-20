<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr5a20y1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr5a20y1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:inbox-full" /></template>
