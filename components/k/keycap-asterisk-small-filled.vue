<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjux1dbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="cjux1dbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-asterisk-small-filled" /></template>
