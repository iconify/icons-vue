<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk_up-b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk_up-b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-check" /></template>
