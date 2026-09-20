<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr6vb84ov.css';
import '../../css/k/kdw9f6x7v.css';
import '../../css/m/mu_a5xqvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr6vb84ov"/><path class="kdw9f6x7v"/><path class="mu_a5xqvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:box" /></template>
