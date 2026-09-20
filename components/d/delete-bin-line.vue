<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g854m9ish.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g854m9ish"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-bin-line" /></template>
