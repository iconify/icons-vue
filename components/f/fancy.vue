<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlbwn-y9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":341,"height":512};
const content = `<path class="xlbwn-y9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:fancy" /></template>
