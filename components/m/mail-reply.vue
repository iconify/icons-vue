<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b33o66b4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b33o66b4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:mail-reply" /></template>
