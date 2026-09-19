<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_h3ksw7p.css';
import '../../css/d/dr4olufdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_h3ksw7p"/><path class="dr4olufdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-up-right-stroke-circle-filled" /></template>
