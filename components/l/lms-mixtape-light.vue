<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttgu38bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ttgu38bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lms-mixtape-light" /></template>
