<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wotq-3b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wotq-3b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-broken" /></template>
