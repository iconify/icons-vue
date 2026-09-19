<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y492fvb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="y492fvb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:anchor" /></template>
