<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tokno44rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tokno44rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:beaker-alt-filled" /></template>
