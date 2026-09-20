<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uveq49prt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uveq49prt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crontab-guru-light" /></template>
