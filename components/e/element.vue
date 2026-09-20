<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jar4abbwg.css';
import '../../css/l/legm6kbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jar4abbwg"/><path class="legm6kbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:element" /></template>
