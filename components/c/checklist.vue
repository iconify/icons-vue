<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsolh_5rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsolh_5rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:checklist" /></template>
