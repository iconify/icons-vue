<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_7j9fb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a_7j9fb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:connector-hex" /></template>
