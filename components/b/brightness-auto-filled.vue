<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv8svybwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv8svybwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brightness-auto-filled" /></template>
