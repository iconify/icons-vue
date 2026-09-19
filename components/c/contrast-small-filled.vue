<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh_-wvb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rh_-wvb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:contrast-small-filled" /></template>
