<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp73zyb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp73zyb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-background" /></template>
