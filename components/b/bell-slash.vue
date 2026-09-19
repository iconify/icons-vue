<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n52uadcfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="n52uadcfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:bell-slash" /></template>
