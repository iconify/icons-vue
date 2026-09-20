<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoaml5x3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoaml5x3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:accessible-icon-alt" /></template>
