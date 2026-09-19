<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrgayabaj.css';
import '../../css/a/amcez-bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jrgayabaj"/><path class="amcez-bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cloud-upload-outline" /></template>
