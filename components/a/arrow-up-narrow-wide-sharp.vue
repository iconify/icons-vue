<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0834k1ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0834k1ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-narrow-wide-sharp" /></template>
