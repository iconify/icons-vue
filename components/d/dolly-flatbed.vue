<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_78iu5-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="k_78iu5-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:dolly-flatbed" /></template>
