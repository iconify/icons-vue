<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y51we8bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="y51we8bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:file-export" /></template>
