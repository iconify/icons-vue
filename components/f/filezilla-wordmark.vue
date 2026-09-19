<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr-3jmbdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vr-3jmbdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:filezilla-wordmark" /></template>
