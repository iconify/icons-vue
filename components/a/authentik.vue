<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejc_0y43h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejc_0y43h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:authentik" /></template>
