<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1_hp2bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="s1_hp2bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:license" /></template>
