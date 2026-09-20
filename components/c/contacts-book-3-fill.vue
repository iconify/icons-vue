<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw4l2odzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw4l2odzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:contacts-book-3-fill" /></template>
