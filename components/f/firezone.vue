<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abozm7xon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="abozm7xon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firezone" /></template>
