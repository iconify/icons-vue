<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okfzjr1ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okfzjr1ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-funnel-outline" /></template>
