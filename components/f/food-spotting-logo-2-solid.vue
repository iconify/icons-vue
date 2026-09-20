<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of82a_iyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="of82a_iyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:food-spotting-logo-2-solid" /></template>
