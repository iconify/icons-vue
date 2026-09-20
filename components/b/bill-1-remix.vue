<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyoux5b6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kyoux5b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bill-1-remix" /></template>
