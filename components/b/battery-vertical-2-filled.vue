<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7w_-bb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7w_-bb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery-vertical-2-filled" /></template>
