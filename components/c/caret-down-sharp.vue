<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzw10rbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nzw10rbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:caret-down-sharp" /></template>
