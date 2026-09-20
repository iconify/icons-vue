<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9o9rzqzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9o9rzqzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:church-outline" /></template>
