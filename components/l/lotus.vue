<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id8txxh5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="id8txxh5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lotus" /></template>
