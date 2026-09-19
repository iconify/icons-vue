<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtqm7xbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vtqm7xbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gimp" /></template>
