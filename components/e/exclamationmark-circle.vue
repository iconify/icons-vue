<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5sw13noc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="w5sw13noc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:exclamationmark-circle" /></template>
