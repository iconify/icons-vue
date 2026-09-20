<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnkgj4m4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xnkgj4m4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bracket-solid" /></template>
