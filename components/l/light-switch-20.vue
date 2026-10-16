<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqfw9ounj.css';
import '../../css/u/uvq5nbclt.css';
import '../../css/j/jiuj5vb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gqfw9ounj"/><path class="uvq5nbclt"/><path class="jiuj5vb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:light-switch-20" /></template>
