<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at93vc5gb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at93vc5gb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:activity-bulk-round" /></template>
