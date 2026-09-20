<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cno3tnb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cno3tnb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-right-up-long-fill" /></template>
