<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nquds8b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nquds8b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:dagger-knife-filled" /></template>
