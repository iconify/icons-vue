<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds9laxbrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds9laxbrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-left-right-sharp-fill" /></template>
