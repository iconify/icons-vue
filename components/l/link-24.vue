<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rde87_mjj.css';
import '../../css/g/g9uw349nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rde87_mjj"/><path class="g9uw349nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:link-24" /></template>
