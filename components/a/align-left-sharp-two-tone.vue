<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8idp9_5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8idp9_5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-left-sharp-two-tone" /></template>
