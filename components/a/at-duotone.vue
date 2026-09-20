<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il93k7bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il93k7bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:at-duotone" /></template>
