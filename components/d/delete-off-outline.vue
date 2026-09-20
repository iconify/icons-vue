<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijozerb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijozerb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:delete-off-outline" /></template>
