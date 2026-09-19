<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7dn_sbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":464};
const content = `<path class="x7dn_sbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:dropbox" /></template>
