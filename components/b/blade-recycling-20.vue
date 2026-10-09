<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lord7rwpc.css';
import '../../css/s/srp1dmbec.css';
import '../../css/n/nuv2zkaui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lord7rwpc"/><path class="srp1dmbec"/><path class="nuv2zkaui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:blade-recycling-20" /></template>
