<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq_pp9coz.css';
import '../../css/v/vslt2rbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer vq_pp9coz"/><path class="duoicon-primary-layer vslt2rbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:credit-card" /></template>
