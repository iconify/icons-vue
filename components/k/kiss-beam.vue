<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miihutl4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="miihutl4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:kiss-beam" /></template>
