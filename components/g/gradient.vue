<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r046gcc4f.css';
import '../../css/f/f7m0-ntgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b r046gcc4f"/><path class="b f7m0-ntgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gradient" /></template>
