<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4q401bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4q401bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:conversation-sync-bold" /></template>
