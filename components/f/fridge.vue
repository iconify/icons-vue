<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zil8_rj-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zil8_rj-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fridge" /></template>
