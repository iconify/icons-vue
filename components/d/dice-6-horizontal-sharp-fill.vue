<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq8ew7via.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gq8ew7via"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-6-horizontal-sharp-fill" /></template>
