<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_e3a2unw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_e3a2unw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ciphermail-light" /></template>
