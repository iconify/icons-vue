<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2cfpnpgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f2cfpnpgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bubble-right" /></template>
