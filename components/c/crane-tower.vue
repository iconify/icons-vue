<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbszl1yhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbszl1yhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:crane-tower" /></template>
