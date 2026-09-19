<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq665t1ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq665t1ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:anchor" /></template>
