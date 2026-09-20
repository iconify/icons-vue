<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2w3uac9z.css';
import '../../css/e/edv2k_o8i.css';
import '../../css/e/eqoo6tulb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="d2w3uac9z"/><path class="edv2k_o8i"/><path class="eqoo6tulb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:dashing-away" /></template>
