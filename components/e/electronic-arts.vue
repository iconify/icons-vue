<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4tdwlciq.css';
import '../../css/c/ca1v0e7az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="m4tdwlciq"/><path class="ca1v0e7az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:electronic-arts" /></template>
