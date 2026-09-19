<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4wi8qbqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i4wi8qbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:layout-alt-02-filled" /></template>
