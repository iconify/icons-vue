<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaax5ob0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaax5ob0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-badge-right-filled" /></template>
