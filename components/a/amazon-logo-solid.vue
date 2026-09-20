<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-kb-fhla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-kb-fhla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:amazon-logo-solid" /></template>
