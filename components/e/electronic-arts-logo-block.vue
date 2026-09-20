<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf5tjob_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xf5tjob_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:electronic-arts-logo-block" /></template>
