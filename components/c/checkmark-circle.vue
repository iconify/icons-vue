<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eu1u2abpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="eu1u2abpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:checkmark-circle" /></template>
