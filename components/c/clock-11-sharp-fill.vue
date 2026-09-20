<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9l-ukbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c9l-ukbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-11-sharp-fill" /></template>
