<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygfchdbyw.css';
import '../../css/m/m8tud7b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ygfchdbyw"/><path class="m8tud7b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-books" /></template>
