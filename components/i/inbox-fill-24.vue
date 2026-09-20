<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eifwhrbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eifwhrbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:inbox-fill-24" /></template>
