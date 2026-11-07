<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p69thbcke.css';
import '../../css/r/r_skykbnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p69thbcke"/><path class="r_skykbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chef-hat-bold-duotone" /></template>
