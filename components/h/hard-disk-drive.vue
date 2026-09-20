<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5kyyl9ov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v5kyyl9ov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:hard-disk-drive" /></template>
