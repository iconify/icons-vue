<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duy3_oprs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="duy3_oprs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:alert-octagon" /></template>
