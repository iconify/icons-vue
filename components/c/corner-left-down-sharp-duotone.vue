<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w56k6_btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w56k6_btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-left-down-sharp-duotone" /></template>
