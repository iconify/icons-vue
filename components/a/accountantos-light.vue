<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enqd_6bdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1084,"height":1074};
const content = `<path class="enqd_6bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:accountantos-light" /></template>
