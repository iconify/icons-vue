<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhsrqh-0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bhsrqh-0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:boson-light" /></template>
