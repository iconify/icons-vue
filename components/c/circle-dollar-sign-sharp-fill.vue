<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozfl8nbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozfl8nbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-dollar-sign-sharp-fill" /></template>
