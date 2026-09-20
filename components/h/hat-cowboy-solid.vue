<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aghg-24qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aghg-24qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hat-cowboy-solid" /></template>
