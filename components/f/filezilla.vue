<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plv2debfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plv2debfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:filezilla" /></template>
