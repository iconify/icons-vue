<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0ft814pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="i0ft814pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-tab-small-filled" /></template>
