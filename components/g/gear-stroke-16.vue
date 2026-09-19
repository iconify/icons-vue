<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8qpv3buc.css';
import '../../css/a/ab4vmibnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o8qpv3buc"/><circle class="ab4vmibnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:gear-stroke-16" /></template>
