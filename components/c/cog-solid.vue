<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loolztbfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="loolztbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cog-solid" /></template>
