<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm_jeenba.css';
import '../../css/k/k0o87zohe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jm_jeenba"/><path class="k0o87zohe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bed-20" /></template>
