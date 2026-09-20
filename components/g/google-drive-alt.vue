<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sprp5wehn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sprp5wehn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:google-drive-alt" /></template>
