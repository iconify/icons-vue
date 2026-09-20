<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljb8flb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljb8flb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:glpi-light" /></template>
