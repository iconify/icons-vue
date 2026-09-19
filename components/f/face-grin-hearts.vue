<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iaip9j5ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iaip9j5ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-grin-hearts" /></template>
