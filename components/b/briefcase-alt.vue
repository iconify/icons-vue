<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmelaowtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmelaowtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:briefcase-alt" /></template>
