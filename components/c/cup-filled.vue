<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmap1pb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmap1pb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cup-filled" /></template>
