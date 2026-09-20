<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxx8dpbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxx8dpbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-up-right-circle" /></template>
