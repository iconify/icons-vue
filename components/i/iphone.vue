<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/memx0ebgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":512};
const content = `<path class="memx0ebgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:iphone" /></template>
