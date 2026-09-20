<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlzy7bc8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlzy7bc8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:google-keep" /></template>
