<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l721n2bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l721n2bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cloud-upload" /></template>
