<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8xonz-pr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8xonz-pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:kurta-01" /></template>
