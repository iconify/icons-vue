<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvuish48u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vvuish48u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-laugh-squint" /></template>
