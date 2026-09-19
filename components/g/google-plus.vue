<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc803kjay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc803kjay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:google-plus" /></template>
