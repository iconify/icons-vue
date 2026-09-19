<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0p-5_bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0p-5_bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:early-access-center" /></template>
