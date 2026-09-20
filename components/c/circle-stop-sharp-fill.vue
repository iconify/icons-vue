<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-8onzbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-8onzbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-stop-sharp-fill" /></template>
