<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk1ggacie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="mk1ggacie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:basketball-11" /></template>
