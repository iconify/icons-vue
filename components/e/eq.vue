<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3q2u3bwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p3q2u3bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:eq" /></template>
