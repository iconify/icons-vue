<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z03ud3uai.css';
import '../../css/f/fq6oz7usv.css';
import '../../css/e/ekyjx0o2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z03ud3uai"/><path class="fq6oz7usv"/><path class="ekyjx0o2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adguard-home" /></template>
