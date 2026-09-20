<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo62owbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo62owbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:lock-2-fill" /></template>
