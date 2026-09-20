<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw73_wxno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw73_wxno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:amg" /></template>
