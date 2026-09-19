<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4ulj1j6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="a4ulj1j6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:battery" /></template>
