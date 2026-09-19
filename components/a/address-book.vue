<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-20n0bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="q-20n0bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:address-book" /></template>
