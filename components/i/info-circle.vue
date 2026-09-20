<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anxjqzbvz.css';
import '../../css/s/si1gihitr.css';
import '../../css/i/i7sr6ubzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anxjqzbvz"/><path class="si1gihitr"/><path class="i7sr6ubzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:info-circle" /></template>
