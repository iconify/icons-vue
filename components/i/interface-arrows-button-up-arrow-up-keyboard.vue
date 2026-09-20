<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emac03b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="emac03b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-arrows-button-up-arrow-up-keyboard" /></template>
