<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zazwy-4qg.css';
import '../../css/i/iwtd4lopd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zazwy-4qg"/><path class="iwtd4lopd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:billing-info-light" /></template>
