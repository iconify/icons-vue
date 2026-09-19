<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_ht3dbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v_ht3dbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:hamsa" /></template>
