<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9sh_qbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9sh_qbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:down-right-arrow" /></template>
