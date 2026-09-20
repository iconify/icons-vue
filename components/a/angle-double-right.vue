<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ial6mtbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ial6mtbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:angle-double-right" /></template>
