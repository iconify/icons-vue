<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk21cmshl.css';
import '../../css/t/tyqxa-33r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk21cmshl"/><path class="tyqxa-33r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:developer-portal" /></template>
