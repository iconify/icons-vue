<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtot_jb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jtot_jb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:headphones" /></template>
