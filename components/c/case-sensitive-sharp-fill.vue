<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz8fuvhmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz8fuvhmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-sensitive-sharp-fill" /></template>
