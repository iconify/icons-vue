<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehuvywcsw.css';
import '../../css/k/k2om2cqop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="ehuvywcsw"/><path class="k2om2cqop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:archive-sharp" /></template>
