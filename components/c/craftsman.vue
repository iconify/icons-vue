<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng1mhigyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng1mhigyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:craftsman" /></template>
