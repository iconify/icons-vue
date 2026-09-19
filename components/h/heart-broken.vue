<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-rpnk9-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="k-rpnk9-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:heart-broken" /></template>
