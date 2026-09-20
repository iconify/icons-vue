<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a104jn7sc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a104jn7sc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fax" /></template>
