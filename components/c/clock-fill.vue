<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7lhebcyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="m7lhebcyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:clock-fill" /></template>
