<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra4arbcap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra4arbcap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flag-chequered-sharp" /></template>
