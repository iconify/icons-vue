<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nybji0bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":488};
const content = `<path class="nybji0bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:coroflot" /></template>
