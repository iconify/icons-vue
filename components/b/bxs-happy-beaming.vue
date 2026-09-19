<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpf0ayjpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpf0ayjpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-happy-beaming" /></template>
