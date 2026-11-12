<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3h177btt.css';
import '../../css/f/f2-iyob1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u3h177btt"/><path class="f2-iyob1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gopeed" /></template>
