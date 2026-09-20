<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi55qob3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xi55qob3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:info-multiple-filled" /></template>
