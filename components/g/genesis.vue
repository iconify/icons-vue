<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if397ns4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if397ns4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:genesis" /></template>
