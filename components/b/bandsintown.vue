<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nivi21b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nivi21b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bandsintown" /></template>
