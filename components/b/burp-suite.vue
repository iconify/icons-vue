<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc1z1abbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc1z1abbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:burp-suite" /></template>
