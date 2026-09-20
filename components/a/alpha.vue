<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdb4764qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdb4764qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alpha" /></template>
