<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at0wrvbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="at0wrvbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:gitpod" /></template>
