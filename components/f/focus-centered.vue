<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvxzujh1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvxzujh1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:focus-centered" /></template>
