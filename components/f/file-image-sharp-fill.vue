<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia5_8rbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ia5_8rbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-image-sharp-fill" /></template>
