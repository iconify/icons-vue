<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2j_xrb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2j_xrb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:edit-detailed-alt-fill" /></template>
