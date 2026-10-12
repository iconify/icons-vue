<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcse7wsih.css';
import '../../css/k/kdbvn80vp.css';
import '../../css/k/kem81wb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kcse7wsih"/><path class="kdbvn80vp"/><path class="kem81wb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-minus-48" /></template>
