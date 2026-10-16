<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_jk-9bgq.css';
import '../../css/m/mr762oh0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k_jk-9bgq"/><path class="mr762oh0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kerbside-charger-48" /></template>
