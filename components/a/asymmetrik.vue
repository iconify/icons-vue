<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8q33qb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m8q33qb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:asymmetrik" /></template>
