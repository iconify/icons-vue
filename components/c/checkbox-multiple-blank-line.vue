<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4hozj88z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4hozj88z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:checkbox-multiple-blank-line" /></template>
