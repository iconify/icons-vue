<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g51-dbv_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g51-dbv_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:life-ring-light" /></template>
