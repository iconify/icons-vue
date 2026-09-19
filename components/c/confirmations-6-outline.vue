<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq39-hb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq39-hb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:confirmations-6-outline" /></template>
