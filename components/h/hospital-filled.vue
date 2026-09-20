<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmd_ombao.css';
import '../../css/e/ejoji3b3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmd_ombao"/><path class="ejoji3b3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:hospital-filled" /></template>
