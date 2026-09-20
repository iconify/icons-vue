<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqgb_dwuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqgb_dwuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-tv-old" /></template>
