<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr1ax_9rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gr1ax_9rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bookmark-plus-solid" /></template>
