<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gne2u-3fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gne2u-3fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hashicorp-packer-light" /></template>
