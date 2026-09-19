<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzii9-bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zzii9-bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:arrow-with-circle-up" /></template>
