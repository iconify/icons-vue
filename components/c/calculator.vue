<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh-9rq0_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh-9rq0_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:calculator" /></template>
