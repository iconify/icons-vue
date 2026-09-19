<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc5h94boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="sc5h94boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:kiss-beam" /></template>
