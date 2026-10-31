<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyu_t2b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyu_t2b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:chevron-right" /></template>
