<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaz8pwiff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-2};
const content = `<path class="yaz8pwiff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:magic-f" /></template>
