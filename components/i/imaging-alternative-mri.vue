<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhnxvf8sx.css';
import '../../css/b/br4kpx8po.css';
import '../../css/w/wnu_u707u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="mhnxvf8sx"/><path class="br4kpx8po"/><path class="wnu_u707u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:imaging-alternative-mri" /></template>
