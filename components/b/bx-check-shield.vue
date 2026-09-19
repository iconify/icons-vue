<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h38or2igg.css';
import '../../css/s/sjerm91lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h38or2igg"/><path class="sjerm91lq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-check-shield" /></template>
