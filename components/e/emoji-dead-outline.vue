<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3va3abzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3va3abzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-dead-outline" /></template>
