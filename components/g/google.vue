<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0s5l9few.css';
import '../../css/y/ywghsebrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0s5l9few"/><path class="ywghsebrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:google" /></template>
