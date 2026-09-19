<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ip_3lbcol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ip_3lbcol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:logo-google" /></template>
