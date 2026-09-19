<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2r13mb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s2r13mb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:bitbucket-logo-32" /></template>
