<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzt5u7bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzt5u7bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-dashed-solid" /></template>
