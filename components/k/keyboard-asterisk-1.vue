<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv6k1030q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv6k1030q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:keyboard-asterisk-1" /></template>
