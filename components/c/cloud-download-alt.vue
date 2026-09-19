<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn7h90e6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="sn7h90e6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cloud-download-alt" /></template>
