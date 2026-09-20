<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a83a_ac-d.css';
import '../../css/j/jy-0-ba4q.css';
import '../../css/d/dheiwnbom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":182};
const content = `<path class="a83a_ac-d"/><path class="jy-0-ba4q"/><path class="dheiwnbom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:amazon-web-services-dark" /></template>
