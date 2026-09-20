<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_e_q-1ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o_e_q-1ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:ambulance-solid" /></template>
