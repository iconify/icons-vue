<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txa3mgbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="txa3mgbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:check" /></template>
