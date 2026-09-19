<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l97ph9b-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l97ph9b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:community-healthworker-outline-24px" /></template>
