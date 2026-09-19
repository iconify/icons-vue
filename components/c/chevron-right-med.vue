<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7u18irpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="z7u18irpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chevron-right-med" /></template>
