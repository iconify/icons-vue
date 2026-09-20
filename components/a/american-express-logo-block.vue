<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnys6xy_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnys6xy_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:american-express-logo-block" /></template>
