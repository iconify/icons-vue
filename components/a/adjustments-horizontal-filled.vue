<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9kuimbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9kuimbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:adjustments-horizontal-filled" /></template>
