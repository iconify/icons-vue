<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-j2nt4-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":684,"height":677};
const content = `<path class="t-j2nt4-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:line" /></template>
