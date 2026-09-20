<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qem3v3brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qem3v3brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-wide-narrow-sharp-fill" /></template>
