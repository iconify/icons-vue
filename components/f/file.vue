<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrghbc5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbrghbc5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file" /></template>
