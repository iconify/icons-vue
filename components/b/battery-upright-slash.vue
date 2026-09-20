<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajs8ko0tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ajs8ko0tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-upright-slash" /></template>
