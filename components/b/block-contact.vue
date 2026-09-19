<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9hcmacxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s9hcmacxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:block-contact" /></template>
