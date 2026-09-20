<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stgx23nhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="stgx23nhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:checkbox-mixed" /></template>
