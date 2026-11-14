<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixgmnoxwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixgmnoxwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:label-important" /></template>
