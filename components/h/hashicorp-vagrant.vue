<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p53mfrb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p53mfrb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-vagrant" /></template>
