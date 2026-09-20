<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nri6v8bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nri6v8bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:label-filled" /></template>
