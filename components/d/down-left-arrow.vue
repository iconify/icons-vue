<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9x_09j0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9x_09j0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:down-left-arrow" /></template>
