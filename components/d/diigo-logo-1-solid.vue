<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvm1ocb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fvm1ocb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:diigo-logo-1-solid" /></template>
