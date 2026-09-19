<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtlavwb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtlavwb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrange-by-numbers-19" /></template>
