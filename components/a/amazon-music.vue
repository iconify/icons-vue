<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppja7jg2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppja7jg2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:amazon-music" /></template>
