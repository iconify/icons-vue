<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ectx9jbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ectx9jbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:lattice-tower-with-lookout-deck" /></template>
