<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfre7ib7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfre7ib7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:directions-01" /></template>
