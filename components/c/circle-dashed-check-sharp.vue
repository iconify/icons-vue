<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-ho668zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-ho668zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-dashed-check-sharp" /></template>
