<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj-l1pbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj-l1pbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:jabber" /></template>
