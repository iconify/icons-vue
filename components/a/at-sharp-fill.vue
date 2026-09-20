<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/era_k9blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="era_k9blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:at-sharp-fill" /></template>
