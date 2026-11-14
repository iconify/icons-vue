<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da-iglb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da-iglb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-check-02" /></template>
