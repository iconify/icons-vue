<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyw-wccpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyw-wccpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-solid" /></template>
