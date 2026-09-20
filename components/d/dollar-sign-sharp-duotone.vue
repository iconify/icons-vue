<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm-yfu1dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-yfu1dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dollar-sign-sharp-duotone" /></template>
