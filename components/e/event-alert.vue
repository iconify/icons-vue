<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbj30sd-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbj30sd-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:event-alert" /></template>
