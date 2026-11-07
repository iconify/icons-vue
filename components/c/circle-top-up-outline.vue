<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npnjj3bqi.css';
import '../../css/l/laen_wd4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npnjj3bqi"/><path class="laen_wd4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-top-up-outline" /></template>
