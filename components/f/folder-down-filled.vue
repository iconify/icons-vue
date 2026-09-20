<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5v_e750t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f5v_e750t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:folder-down-filled" /></template>
