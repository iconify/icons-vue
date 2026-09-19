<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n50wq5bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n50wq5bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-filament-spot" /></template>
