<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmbc5ub3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xmbc5ub3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:google-drive-outline" /></template>
