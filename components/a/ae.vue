<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9gujfbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9gujfbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ae" /></template>
