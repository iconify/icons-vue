<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_qs3bckf.css';
import '../../css/p/pzkhnyb6c.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 f_qs3bckf"/><path class="clr-i-outline clr-i-outline-path-2 pzkhnyb6c"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:eye-show-line" /></template>
