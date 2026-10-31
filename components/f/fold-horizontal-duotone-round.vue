<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5ws0xb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5ws0xb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fold-horizontal-duotone-round" /></template>
