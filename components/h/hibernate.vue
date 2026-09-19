<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdtmj-bqy.css';
import '../../css/n/nlvvtjrbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vdtmj-bqy"/><path class="nlvvtjrbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:hibernate" /></template>
