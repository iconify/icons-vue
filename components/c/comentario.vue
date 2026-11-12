<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xatinu_2d.css';
import '../../css/v/v1w24bcca.css';
import '../../css/c/cn8nznbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xatinu_2d"/><path class="v1w24bcca"/><path class="cn8nznbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:comentario" /></template>
