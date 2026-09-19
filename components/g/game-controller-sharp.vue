<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-odk-bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z-odk-bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:game-controller-sharp" /></template>
