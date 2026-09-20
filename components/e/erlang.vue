<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn5ti5b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn5ti5b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:erlang" /></template>
