<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ut_yg9bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ut_yg9bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-open-two-tone" /></template>
