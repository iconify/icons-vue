<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2dqk2sur.css';
import '../../css/t/t3kyidv8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g2dqk2sur"/><path class="t3kyidv8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cr-nmaster" /></template>
