<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlxi2zhro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="tlxi2zhro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-digit-two-small-filled" /></template>
