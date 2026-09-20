<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc2r4ounr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc2r4ounr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fast-forward-sharp-duotone" /></template>
