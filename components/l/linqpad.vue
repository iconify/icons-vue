<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl_5u-arg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":485,"height":512};
const content = `<path class="wl_5u-arg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:linqpad" /></template>
