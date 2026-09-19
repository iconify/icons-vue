<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9k06bc4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g9k06bc4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hootsuite" /></template>
