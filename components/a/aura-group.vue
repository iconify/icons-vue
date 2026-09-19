<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpyseabnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpyseabnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aura-group" /></template>
