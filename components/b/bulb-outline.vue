<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8iz40ljm.css';
import '../../css/d/dit6uybka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8iz40ljm"/><path class="dit6uybka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bulb-outline" /></template>
