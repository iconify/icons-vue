<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wydskcb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wydskcb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:affinity-publiser-logo-block" /></template>
