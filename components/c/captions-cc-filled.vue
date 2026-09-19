<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3tpki16g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3tpki16g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:captions-cc-filled" /></template>
