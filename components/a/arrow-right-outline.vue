<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eivc34lmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eivc34lmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-right-outline" /></template>
