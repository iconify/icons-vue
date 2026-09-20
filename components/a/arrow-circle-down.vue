<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldtu0gu7y.css';
import '../../css/t/tdnjtvgqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldtu0gu7y"/><path class="tdnjtvgqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-circle-down" /></template>
