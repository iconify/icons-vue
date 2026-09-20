<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmpez3udl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmpez3udl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-sharp-duotone" /></template>
