<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-v_r1sov.css';
import '../../css/k/k2n9vabow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b-v_r1sov"/><path class="k2n9vabow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:document-security" /></template>
