<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muf9lpbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="muf9lpbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-site-alt2" /></template>
