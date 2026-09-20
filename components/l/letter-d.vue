<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws-5jebqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ws-5jebqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-d" /></template>
