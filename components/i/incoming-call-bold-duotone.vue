<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjrrq5bwn.css';
import '../../css/j/j05r12o9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjrrq5bwn"/><path class="j05r12o9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:incoming-call-bold-duotone" /></template>
