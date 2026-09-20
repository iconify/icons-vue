<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2n94b11u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c2n94b11u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-boundary-light" /></template>
