<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sutcchbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sutcchbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-laugh-beam" /></template>
