<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp2h-rbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bp2h-rbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:filezilla" /></template>
