<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv4r6ac-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="vv4r6ac-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clipboard-plus-solid" /></template>
