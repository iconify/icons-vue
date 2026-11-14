<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhnm9mbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhnm9mbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delete-01" /></template>
