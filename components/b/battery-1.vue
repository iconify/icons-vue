<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivs45cbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivs45cbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-1" /></template>
