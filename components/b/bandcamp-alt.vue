<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii_q9nbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii_q9nbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bandcamp-alt" /></template>
