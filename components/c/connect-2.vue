<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf81sm_hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":17};
const content = `<path class="rf81sm_hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:connect-2" /></template>
