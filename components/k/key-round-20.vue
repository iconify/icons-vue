<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_31tneyb.css';
import '../../css/p/p1ariqbgg.css';
import '../../css/s/sk8e-4p4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z_31tneyb"/><path class="p1ariqbgg"/><path class="sk8e-4p4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-round-20" /></template>
