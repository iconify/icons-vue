<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pggf_ba-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pggf_ba-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:claude-clawd" /></template>
