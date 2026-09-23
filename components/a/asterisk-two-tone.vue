<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgddtab4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgddtab4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:asterisk-two-tone" /></template>
