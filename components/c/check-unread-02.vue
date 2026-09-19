<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjmaoon3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjmaoon3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:check-unread-02" /></template>
