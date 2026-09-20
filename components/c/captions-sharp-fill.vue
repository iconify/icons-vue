<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvknj4vry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yvknj4vry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:captions-sharp-fill" /></template>
