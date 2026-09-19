<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hr_oih2cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="hr_oih2cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:adjustment-horizon" /></template>
