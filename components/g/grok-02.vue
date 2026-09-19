<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyrcwhxhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyrcwhxhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:grok-02" /></template>
