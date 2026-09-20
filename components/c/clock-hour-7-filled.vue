<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boe6k9bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boe6k9bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-7-filled" /></template>
