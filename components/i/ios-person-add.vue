<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg-7l1u1i.css';
import '../../css/f/fua5fmpqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jg-7l1u1i"/><path class="fua5fmpqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-person-add" /></template>
