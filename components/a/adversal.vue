<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaxi7qn1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vaxi7qn1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:adversal" /></template>
