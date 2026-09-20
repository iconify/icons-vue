<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2-tugbug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2-tugbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:maas" /></template>
