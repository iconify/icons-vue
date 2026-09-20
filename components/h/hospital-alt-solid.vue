<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia6rq2b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ia6rq2b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hospital-alt-solid" /></template>
