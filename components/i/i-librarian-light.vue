<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkw3vswdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wkw3vswdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:i-librarian-light" /></template>
