<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9q15b9rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j9q15b9rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:fitbit" /></template>
