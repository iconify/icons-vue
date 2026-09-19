<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ax2g1qbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ax2g1qbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:any-solvent" /></template>
