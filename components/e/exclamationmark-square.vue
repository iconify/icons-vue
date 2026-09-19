<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlsqcp-7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tlsqcp-7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:exclamationmark-square" /></template>
