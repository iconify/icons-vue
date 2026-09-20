<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb-r8iu1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cb-r8iu1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-chevron-right-sharp-fill" /></template>
