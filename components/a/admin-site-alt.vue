<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn-tllbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dn-tllbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:admin-site-alt" /></template>
