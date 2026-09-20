<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avt6vcbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avt6vcbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:isc2" /></template>
