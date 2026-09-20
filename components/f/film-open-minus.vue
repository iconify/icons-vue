<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss3yoypvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss3yoypvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-minus" /></template>
