<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5piqkb1i.css';
import '../../css/m/ms1j4bchs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e5piqkb1i"/><path class="ms1j4bchs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-ionic-outline" /></template>
