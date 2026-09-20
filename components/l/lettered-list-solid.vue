<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvk-0wi1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvk-0wi1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lettered-list-solid" /></template>
