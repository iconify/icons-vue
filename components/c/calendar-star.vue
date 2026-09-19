<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwcupbbaj.css';
import '../../css/d/dfc4wub2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwcupbbaj"/><path class="dfc4wub2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:calendar-star" /></template>
