<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrehdqb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mrehdqb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoiceshelf-dark" /></template>
