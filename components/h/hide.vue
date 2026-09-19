<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s00qr5bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s00qr5bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:hide" /></template>
