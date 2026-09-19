<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfjtvjbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfjtvjbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:arrow-up-02" /></template>
