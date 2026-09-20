<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqvu_ab2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqvu_ab2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:behance-logo-bold" /></template>
