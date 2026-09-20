<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atl1ue-ei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atl1ue-ei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:bluesky" /></template>
