<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm_oytb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm_oytb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jetpack-compose" /></template>
