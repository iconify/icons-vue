<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8y89f8sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8y89f8sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:anchor" /></template>
