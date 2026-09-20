<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsofzrbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsofzrbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badge-off" /></template>
