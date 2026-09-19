<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1al5gu-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t1al5gu-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:eventbrite" /></template>
